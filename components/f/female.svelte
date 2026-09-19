<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f--u3xscy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="f--u3xscy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:female" {...props}></Icon>
