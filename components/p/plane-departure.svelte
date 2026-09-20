<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cso69g_tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cso69g_tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:plane-departure" {...props}></Icon>
