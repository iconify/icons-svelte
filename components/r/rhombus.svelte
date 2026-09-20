<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb39vdkqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jb39vdkqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:rhombus" {...props}></Icon>
