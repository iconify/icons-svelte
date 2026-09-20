<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdnovq2fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fdnovq2fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openchangelog" {...props}></Icon>
