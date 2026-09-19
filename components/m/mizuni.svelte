<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twxgav9tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="twxgav9tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:mizuni" {...props}></Icon>
