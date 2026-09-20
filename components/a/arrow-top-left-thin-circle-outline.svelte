<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx699ab2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx699ab2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-top-left-thin-circle-outline" {...props}></Icon>
