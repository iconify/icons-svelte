<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdrrclbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdrrclbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-v-circle" {...props}></Icon>
