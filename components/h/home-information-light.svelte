<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4dsqac7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f4dsqac7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:home-information-light" {...props}></Icon>
