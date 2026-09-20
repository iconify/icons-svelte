<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihbn3ee0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ihbn3ee0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:bold" {...props}></Icon>
