<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbn2bd74u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fbn2bd74u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:onion" {...props}></Icon>
