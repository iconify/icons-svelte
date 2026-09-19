<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0q8216sb.css';
import '../../css/u/uf53occ4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k0q8216sb"/><circle class="uf53occ4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:cue" {...props}></Icon>
