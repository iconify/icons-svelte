<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/eivil5x4j.css';
import '../../css/j/j5wzuiucp.css';
import '../../css/w/w49j0rbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGB86rKcgl"><g class="ft5dv1b6b"><path class="eivil5x4j"/><path class="j5wzuiucp"/></g></mask></defs><path mask="url(#SVGB86rKcgl)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folders-line-duotone" {...props}></Icon>
