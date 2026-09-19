<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnex464ct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="gnex464ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:keyboard-chevron-compact-down" {...props}></Icon>
