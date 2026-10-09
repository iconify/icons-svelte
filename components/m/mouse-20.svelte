<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/non8y593o.css';
import '../../css/b/bbclq6bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="non8y593o"/><path class="bbclq6bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mouse-20" {...props}></Icon>
