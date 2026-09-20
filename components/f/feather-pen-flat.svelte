<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mvkrd2b5g.css';
import '../../css/f/f1pe3pbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mvkrd2b5g"/><path clip-rule="evenodd" class="f1pe3pbmj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:feather-pen-flat" {...props}></Icon>
