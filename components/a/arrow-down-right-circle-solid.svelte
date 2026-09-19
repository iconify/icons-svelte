<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gty_nob9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gty_nob9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrow-down-right-circle-solid" {...props}></Icon>
