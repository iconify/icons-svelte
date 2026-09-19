<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_b0fqbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_b0fqbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:note-add" {...props}></Icon>
