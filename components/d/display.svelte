<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_-n5y9kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m_-n5y9kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:display" {...props}></Icon>
