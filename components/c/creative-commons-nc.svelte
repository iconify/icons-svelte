<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm9-6ac6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qm9-6ac6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:creative-commons-nc" {...props}></Icon>
