<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh-l_-f6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fh-l_-f6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:macrumors-light" {...props}></Icon>
