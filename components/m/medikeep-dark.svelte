<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkzqvsb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tkzqvsb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:medikeep-dark" {...props}></Icon>
