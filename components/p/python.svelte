<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxmbj9awl.css';
import '../../css/c/cv0y2ubog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxmbj9awl"/><path class="cv0y2ubog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:python" {...props}></Icon>
