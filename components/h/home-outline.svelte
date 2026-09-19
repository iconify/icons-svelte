<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr1m_4c0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr1m_4c0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:home-outline" {...props}></Icon>
