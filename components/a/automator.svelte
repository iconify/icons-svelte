<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gajh3do4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":474,"height":512};
const content = `<path class="gajh3do4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:automator" {...props}></Icon>
