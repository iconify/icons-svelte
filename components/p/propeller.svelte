<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uja-nib7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uja-nib7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:propeller" {...props}></Icon>
