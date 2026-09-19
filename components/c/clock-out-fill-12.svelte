<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lirk0ib9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lirk0ib9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clock-out-fill-12" {...props}></Icon>
