<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn2ngg-tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kn2ngg-tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:metal-hand" {...props}></Icon>
