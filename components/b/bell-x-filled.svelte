<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xba6fzbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xba6fzbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-x-filled" {...props}></Icon>
