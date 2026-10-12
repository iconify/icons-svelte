<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myys72pto.css';
import '../../css/v/vk89q7biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="myys72pto"/><path class="vk89q7biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-out-fill-20" {...props}></Icon>
