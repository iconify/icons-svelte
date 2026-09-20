<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jab7xhb0n.css';
import '../../css/v/vla3-w5tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jab7xhb0n"/><path class="vla3-w5tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:magento" {...props}></Icon>
