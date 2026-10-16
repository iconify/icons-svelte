<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9km6db4h.css';
import '../../css/o/ozsetf5vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w9km6db4h"/><path class="ozsetf5vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:axe-20" {...props}></Icon>
