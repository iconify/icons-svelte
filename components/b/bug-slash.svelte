<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/o/o7psohbfh.css';
import '../../css/q/q90fv6qec.css';
import '../../css/a/a2wwsgbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o7psohbfh"/><path class="q90fv6qec"/><path class="a2wwsgbar"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bug-slash" {...props}></Icon>
