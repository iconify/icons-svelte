<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae8y8wkyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ae8y8wkyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gym-bag" {...props}></Icon>
