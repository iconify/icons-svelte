<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whd7w6bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whd7w6bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:forward-linear" {...props}></Icon>
