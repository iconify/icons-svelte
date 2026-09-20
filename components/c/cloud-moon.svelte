<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcwm9zbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcwm9zbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:cloud-moon" {...props}></Icon>
