<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vobn2vo6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":472};
const content = `<path class="vobn2vo6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:android-alt" {...props}></Icon>
