<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd6t3v_tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd6t3v_tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:group-2-line" {...props}></Icon>
