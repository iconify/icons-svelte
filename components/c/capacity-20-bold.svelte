<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiabdabxj.css';
import '../../css/z/z_3gq8xqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wiabdabxj"/><path class="z_3gq8xqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:capacity-20-bold" {...props}></Icon>
