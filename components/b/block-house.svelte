<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkdhynb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qkdhynb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:block-house" {...props}></Icon>
