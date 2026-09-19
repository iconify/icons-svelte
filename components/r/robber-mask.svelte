<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0vk71j4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o0vk71j4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:robber-mask" {...props}></Icon>
