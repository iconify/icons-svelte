<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxzq55xig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fxzq55xig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:play-circle" {...props}></Icon>
