<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0q0dtbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u0q0dtbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-dot-bold" {...props}></Icon>
