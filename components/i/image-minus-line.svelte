<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz-xaq9tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz-xaq9tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:image-minus-line" {...props}></Icon>
