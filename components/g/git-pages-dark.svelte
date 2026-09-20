<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxg3z72tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lxg3z72tz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:git-pages-dark" {...props}></Icon>
