<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwcvxfb2t.css';
import '../../css/y/yo1jbmxse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dwcvxfb2t"/><path class="yo1jbmxse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mug-20-bold" {...props}></Icon>
