<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of9-g8y0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="of9-g8y0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:chevron-double-right" {...props}></Icon>
