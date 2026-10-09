<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y04gfnbxb.css';
import '../../css/t/t170-qrdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y04gfnbxb"/><path class="t170-qrdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:eye-20" {...props}></Icon>
