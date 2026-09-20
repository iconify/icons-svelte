<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kefy6rber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kefy6rber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:man" {...props}></Icon>
