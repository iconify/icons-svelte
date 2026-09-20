<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/not9azb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="not9azb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:memcached" {...props}></Icon>
