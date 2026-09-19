<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v38xawbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v38xawbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:archive" {...props}></Icon>
