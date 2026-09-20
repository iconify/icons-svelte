<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh3owmujd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="hh3owmujd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:calendar-add" {...props}></Icon>
