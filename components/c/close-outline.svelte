<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toyx_jwrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="toyx_jwrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:close-outline" {...props}></Icon>
