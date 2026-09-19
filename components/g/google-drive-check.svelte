<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-a17nn7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-a17nn7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:google-drive-check" {...props}></Icon>
