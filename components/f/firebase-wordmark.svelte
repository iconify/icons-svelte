<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqoz608tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bqoz608tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:firebase-wordmark" {...props}></Icon>
