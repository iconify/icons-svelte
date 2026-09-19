<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usmgq6brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="usmgq6brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:heart-solid" {...props}></Icon>
