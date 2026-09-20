<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6xk0f5fc.css';
import '../../css/m/mi_ecrt5s.css';
import '../../css/b/bst7l4f5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f6xk0f5fc"/><path class="mi_ecrt5s"/><path class="bst7l4f5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:minecraft-creeper" {...props}></Icon>
