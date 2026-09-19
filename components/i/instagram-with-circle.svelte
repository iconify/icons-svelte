<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es0hutbci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="es0hutbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:instagram-with-circle" {...props}></Icon>
