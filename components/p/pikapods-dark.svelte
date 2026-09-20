<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f__75lbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f__75lbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pikapods-dark" {...props}></Icon>
