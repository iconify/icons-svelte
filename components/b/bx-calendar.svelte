<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf6rktajg.css';
import '../../css/f/fd0ve6bab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf6rktajg"/><path class="fd0ve6bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-calendar" {...props}></Icon>
