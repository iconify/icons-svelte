<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q81dddbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q81dddbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-find-outline" {...props}></Icon>
