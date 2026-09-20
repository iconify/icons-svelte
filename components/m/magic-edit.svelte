<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-5_mcc4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-5_mcc4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:magic-edit" {...props}></Icon>
