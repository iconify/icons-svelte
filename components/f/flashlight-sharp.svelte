<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prcy1udmo.css';
import '../../css/j/jnlj8ybtf.css';
import '../../css/j/jn0obg5tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="prcy1udmo"/><ellipse class="jnlj8ybtf"/><path class="jn0obg5tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:flashlight-sharp" {...props}></Icon>
