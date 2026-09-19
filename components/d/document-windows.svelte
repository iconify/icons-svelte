<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgamf5ziv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgamf5ziv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:document-windows" {...props}></Icon>
