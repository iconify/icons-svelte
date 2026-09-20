<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym9ljfbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ym9ljfbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:credit-card-plus" {...props}></Icon>
