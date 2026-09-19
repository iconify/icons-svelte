<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hss024hkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hss024hkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:heart-bold" {...props}></Icon>
