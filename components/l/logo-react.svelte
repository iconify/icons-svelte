<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npvpxe_he.css';
import '../../css/e/e7idfvbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="npvpxe_he"/><path class="e7idfvbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-react" {...props}></Icon>
