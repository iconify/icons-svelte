<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2ckhrb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="n2ckhrb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:atm" {...props}></Icon>
