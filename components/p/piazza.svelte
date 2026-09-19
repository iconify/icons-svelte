<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1m_nbbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="p1m_nbbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:piazza" {...props}></Icon>
