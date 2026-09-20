<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcpskw6nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pcpskw6nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-sort-vertical-bold" {...props}></Icon>
