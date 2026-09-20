<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h05fbqbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h05fbqbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:comment-next" {...props}></Icon>
