<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0kjwnbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="e0kjwnbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:gnome-wordmark" {...props}></Icon>
