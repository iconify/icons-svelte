<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkij9-1rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tkij9-1rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:power-pole" {...props}></Icon>
