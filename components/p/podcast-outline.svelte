<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqwv9fbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sqwv9fbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:podcast-outline" {...props}></Icon>
