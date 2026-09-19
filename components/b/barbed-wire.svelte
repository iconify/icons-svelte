<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zql7dlb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zql7dlb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:barbed-wire" {...props}></Icon>
