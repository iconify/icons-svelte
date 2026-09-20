<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm0pnqbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zm0pnqbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hand-stars-outline" {...props}></Icon>
