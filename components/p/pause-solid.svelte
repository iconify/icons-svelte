<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_8kpcwhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_8kpcwhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:pause-solid" {...props}></Icon>
