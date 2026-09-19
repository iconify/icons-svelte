<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w81d89beh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="w81d89beh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clock-fill-12" {...props}></Icon>
