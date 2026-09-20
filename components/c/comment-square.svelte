<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk0nyobdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="pk0nyobdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:comment-square" {...props}></Icon>
