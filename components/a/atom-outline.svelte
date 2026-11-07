<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3nbddbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a3nbddbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:atom-outline" {...props}></Icon>
