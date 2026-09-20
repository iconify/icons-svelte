<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcvti56rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="rcvti56rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:chevron-left" {...props}></Icon>
