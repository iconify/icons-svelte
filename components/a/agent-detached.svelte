<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6lprsbiy.css';
import '../../css/s/snqitqbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p6lprsbiy"/><path class="snqitqbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:agent-detached" {...props}></Icon>
