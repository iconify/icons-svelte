<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gvhlp8bsj.css';
import '../../css/w/wxw5rwbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gvhlp8bsj"/><path class="wxw5rwbey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ginetex:mild-professional-wet-cleaning" {...props}></Icon>
