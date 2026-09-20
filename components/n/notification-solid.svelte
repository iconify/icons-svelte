<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua9nt7b1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ua9nt7b1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:notification-solid" {...props}></Icon>
