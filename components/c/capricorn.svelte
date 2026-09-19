<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev2g9p6tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ev2g9p6tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:capricorn" {...props}></Icon>
