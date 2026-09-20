<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1ik_cbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1ik_cbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bag-suitcase" {...props}></Icon>
