<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g37t12bqh.css';
import '../../css/n/n83impbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g37t12bqh"/><path class="n83impbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:dice-16" {...props}></Icon>
