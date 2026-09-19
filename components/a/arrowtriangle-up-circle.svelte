<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz4zuhgej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="gz4zuhgej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowtriangle-up-circle" {...props}></Icon>
