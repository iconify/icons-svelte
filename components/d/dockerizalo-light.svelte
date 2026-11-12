<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhkel2bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uhkel2bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dockerizalo-light" {...props}></Icon>
