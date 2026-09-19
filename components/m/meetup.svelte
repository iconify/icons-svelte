<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kasexvb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kasexvb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:meetup" {...props}></Icon>
