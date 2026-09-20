<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/earlxnb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="earlxnb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:at" {...props}></Icon>
