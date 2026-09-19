<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4u7qfb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="h4u7qfb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:electric-light-bulb-small-filled" {...props}></Icon>
