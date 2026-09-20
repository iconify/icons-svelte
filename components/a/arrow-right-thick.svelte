<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrldg9bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrldg9bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:arrow-right-thick" {...props}></Icon>
