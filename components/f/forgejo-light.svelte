<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvqg2ebaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vvqg2ebaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:forgejo-light" {...props}></Icon>
