<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gko9cn1tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gko9cn1tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:balloon" {...props}></Icon>
