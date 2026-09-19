<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqd9so5au.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqd9so5au"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-card" {...props}></Icon>
