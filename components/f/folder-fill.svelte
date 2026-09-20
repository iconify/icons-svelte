<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg9yb5n6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rg9yb5n6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-fill" {...props}></Icon>
