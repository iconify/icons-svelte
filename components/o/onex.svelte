<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ics67bbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1545,"height":1151};
const content = `<path class="ics67bbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:onex" {...props}></Icon>
