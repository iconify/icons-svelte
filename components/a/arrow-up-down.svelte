<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0y3xy14v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0y3xy14v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-up-down" {...props}></Icon>
