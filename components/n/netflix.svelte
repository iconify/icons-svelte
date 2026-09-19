<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw-jtor1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zw-jtor1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:netflix" {...props}></Icon>
