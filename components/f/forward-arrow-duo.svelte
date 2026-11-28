<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9xbjpe9s.css';
import '../../css/i/icurep0mw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9xbjpe9s secondary"/><path class="icurep0mw primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:forward-arrow-duo" {...props}></Icon>
