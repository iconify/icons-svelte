<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtn--hnvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xtn--hnvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:pass-fill" {...props}></Icon>
