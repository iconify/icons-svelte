<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq2872btg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bq2872btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:glass-mug-variant-off" {...props}></Icon>
