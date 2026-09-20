<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utdu4ccld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="utdu4ccld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:download-square-bold" {...props}></Icon>
