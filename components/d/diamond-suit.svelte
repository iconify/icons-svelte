<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwju7lbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nwju7lbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:diamond-suit" {...props}></Icon>
