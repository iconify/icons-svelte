<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de63-bcoq.css';
import '../../css/g/gmk8tebem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="de63-bcoq"/><path class="gmk8tebem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:noise-reduction-48-bold" {...props}></Icon>
