<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtmx9jbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtmx9jbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:mic-pause" {...props}></Icon>
