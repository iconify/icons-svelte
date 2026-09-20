<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svqw_06gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svqw_06gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-l-circle" {...props}></Icon>
