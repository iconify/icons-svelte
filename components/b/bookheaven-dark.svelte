<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guvmkgbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="guvmkgbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bookheaven-dark" {...props}></Icon>
