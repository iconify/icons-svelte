<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaxfskgkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":420,"height":850};
const content = `<path class="kaxfskgkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:ribbon" {...props}></Icon>
