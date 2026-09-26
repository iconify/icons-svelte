<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g232_jeaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g232_jeaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:content-navigator-sync-error" {...props}></Icon>
