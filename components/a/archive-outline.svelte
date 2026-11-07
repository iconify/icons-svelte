<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-c2tob9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u-c2tob9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-outline" {...props}></Icon>
