<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dodx40jvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dodx40jvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:moon-stars" {...props}></Icon>
