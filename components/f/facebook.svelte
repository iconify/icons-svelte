<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnt67v5tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="pnt67v5tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:facebook" {...props}></Icon>
