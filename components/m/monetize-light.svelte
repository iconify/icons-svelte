<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1-exye0j.css';
import '../../css/i/i7h1uo08v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1-exye0j"/><path class="i7h1uo08v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:monetize-light" {...props}></Icon>
