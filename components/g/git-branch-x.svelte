<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wta2nkbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wta2nkbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:git-branch-x" {...props}></Icon>
