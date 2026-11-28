<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic2dd_baz.css';
import '../../css/d/do9zq7gwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ic2dd_baz secondary"/><path class="do9zq7gwa primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:heptagon-duo" {...props}></Icon>
