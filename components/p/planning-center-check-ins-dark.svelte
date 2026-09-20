<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avdrmxbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="avdrmxbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planning-center-check-ins-dark" {...props}></Icon>
