<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uc0yydbxj.css';
import '../../css/t/tcutiwbel.css';
import '../../css/r/racfkwbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="uc0yydbxj"/><path class="tcutiwbel"/><path class="racfkwbdc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:briefcase5-filled" {...props}></Icon>
