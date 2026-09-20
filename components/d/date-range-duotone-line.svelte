<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukm9jj2re.css';
import '../../css/q/q6wu4bc0t.css';
import '../../css/r/r5knwvbfg.css';
import '../../css/g/ga2yrzb2l.css';
import '../../css/e/eefrnxbyo.css';
import '../../css/w/w49j0rbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGDnrO1b2A"><g class="ukm9jj2re"><path class="q6wu4bc0t"/><path class="r5knwvbfg"/><rect class="ga2yrzb2l"/><path class="eefrnxbyo"/></g></mask></defs><path mask="url(#SVGDnrO1b2A)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:date-range-duotone-line" {...props}></Icon>
