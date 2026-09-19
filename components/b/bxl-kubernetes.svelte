<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4zh9ut5i.css';
import '../../css/j/jumj_bc-f.css';
import '../../css/a/aww_3tzev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4zh9ut5i"/><path class="jumj_bc-f"/><path class="aww_3tzev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-kubernetes" {...props}></Icon>
