<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljsqm-boc.css';
import '../../css/d/dklea-b1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ljsqm-boc"/><path class="dklea-b1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:guitar-folk-16" {...props}></Icon>
