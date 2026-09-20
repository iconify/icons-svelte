<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd5jlqbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bd5jlqbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:gitea" {...props}></Icon>
