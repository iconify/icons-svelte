<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o59f1m2si.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="o59f1m2si"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:archery" {...props}></Icon>
