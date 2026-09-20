<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2nk0cb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2nk0cb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:icicibank" {...props}></Icon>
