<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3m_nk0lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1664};
const content = `<path class="n3m_nk0lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:no-comment-bubble" {...props}></Icon>
