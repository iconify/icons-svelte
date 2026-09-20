<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmvvp4bne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":226};
const content = `<path class="vmvvp4bne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bluesky" {...props}></Icon>
