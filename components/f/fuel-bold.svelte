<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz0f_-b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zz0f_-b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:fuel-bold" {...props}></Icon>
