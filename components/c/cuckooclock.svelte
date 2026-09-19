<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7qer0kun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="l7qer0kun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cuckooclock" {...props}></Icon>
