<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcab2sbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qcab2sbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-infinite-outline" {...props}></Icon>
