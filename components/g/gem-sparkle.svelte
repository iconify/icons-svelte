<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xibuolb2y.css';
import '../../css/c/c85egjb-l.css';
import '../../css/a/ap9enlbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xibuolb2y"/><path class="c85egjb-l"/><path class="ap9enlbhu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gem-sparkle" {...props}></Icon>
