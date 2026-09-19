<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttw1qx63j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ttw1qx63j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:battery-car" {...props}></Icon>
