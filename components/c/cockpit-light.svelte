<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7xf0gald.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b7xf0gald"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cockpit-light" {...props}></Icon>
