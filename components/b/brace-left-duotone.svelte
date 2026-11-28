<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic2ffcbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ic2ffcbfm primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:brace-left-duotone" {...props}></Icon>
