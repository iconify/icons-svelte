<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sknrdgbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sknrdgbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:memories-dark" {...props}></Icon>
