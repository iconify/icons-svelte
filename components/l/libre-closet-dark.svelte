<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljaybjbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ljaybjbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:libre-closet-dark" {...props}></Icon>
