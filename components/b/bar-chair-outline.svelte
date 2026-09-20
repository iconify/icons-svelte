<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkwaqebax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rkwaqebax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bar-chair-outline" {...props}></Icon>
