<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0cd28b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="s0cd28b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-c2sc" {...props}></Icon>
