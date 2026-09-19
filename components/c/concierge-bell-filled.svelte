<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb_j-j7cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tb_j-j7cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:concierge-bell-filled" {...props}></Icon>
