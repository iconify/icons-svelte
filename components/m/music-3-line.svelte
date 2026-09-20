<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgcif9d1i.css';
import '../../css/s/selzvwqut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgcif9d1i"/><path class="selzvwqut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:music-3-line" {...props}></Icon>
