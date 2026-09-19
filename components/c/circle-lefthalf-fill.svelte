<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3khy7bbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="u3khy7bbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:circle-lefthalf-fill" {...props}></Icon>
