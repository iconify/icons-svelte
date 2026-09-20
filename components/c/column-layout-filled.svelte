<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd1acfboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd1acfboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:column-layout-filled" {...props}></Icon>
