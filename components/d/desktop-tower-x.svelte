<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn6kv1b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sn6kv1b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:desktop-tower-x" {...props}></Icon>
