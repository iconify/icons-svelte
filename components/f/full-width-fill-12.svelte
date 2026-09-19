<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjm5n7boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mjm5n7boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:full-width-fill-12" {...props}></Icon>
