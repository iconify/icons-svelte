<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt2wc0bfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt2wc0bfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:refresh-solid" {...props}></Icon>
