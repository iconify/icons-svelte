<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pve4lhbsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pve4lhbsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:check-box-with-check" {...props}></Icon>
