<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8wh20b4s.css';
import '../../css/t/tatmy1kfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s8wh20b4s"/><path class="tatmy1kfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:cutlery-fill-20" {...props}></Icon>
