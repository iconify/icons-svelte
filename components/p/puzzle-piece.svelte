<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-4nfhedr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-4nfhedr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:puzzle-piece" {...props}></Icon>
