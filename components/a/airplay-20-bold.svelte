<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix3svnbbt.css';
import '../../css/g/gj1g8xb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ix3svnbbt"/><path class="gj1g8xb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:airplay-20-bold" {...props}></Icon>
