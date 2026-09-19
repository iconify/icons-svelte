<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1s4z7prw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u1s4z7prw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:robots" {...props}></Icon>
