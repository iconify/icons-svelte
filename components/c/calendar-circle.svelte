<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn94ohb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="wn94ohb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:calendar-circle" {...props}></Icon>
