<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oav6wl84e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="oav6wl84e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:battery" {...props}></Icon>
