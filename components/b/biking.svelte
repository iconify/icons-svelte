<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1g9gabpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="h1g9gabpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:biking" {...props}></Icon>
