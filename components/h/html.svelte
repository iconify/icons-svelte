<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7x18sbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="o7x18sbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:html" {...props}></Icon>
