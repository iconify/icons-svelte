<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t__y3ywkr.css';
import '../../css/o/ocjdsognq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t__y3ywkr"/><path class="ocjdsognq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-skip-backward" {...props}></Icon>
