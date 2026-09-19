<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b69v5bj7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b69v5bj7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:power-plug" {...props}></Icon>
