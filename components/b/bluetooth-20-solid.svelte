<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfuv_1wwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mfuv_1wwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:bluetooth-20-solid" {...props}></Icon>
