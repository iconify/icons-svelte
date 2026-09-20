<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yur87nwye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yur87nwye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:droplet-minus" {...props}></Icon>
