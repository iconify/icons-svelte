<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otpdxvb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otpdxvb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:my-sites-horizon" {...props}></Icon>
