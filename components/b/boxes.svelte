<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsqyjmb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="bsqyjmb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:boxes" {...props}></Icon>
