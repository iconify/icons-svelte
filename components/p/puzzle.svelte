<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2-go7evs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":35,"height":32};
const content = `<path class="m2-go7evs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:puzzle" {...props}></Icon>
