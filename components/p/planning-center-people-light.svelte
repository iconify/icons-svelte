<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it2cgzg4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="it2cgzg4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planning-center-people-light" {...props}></Icon>
