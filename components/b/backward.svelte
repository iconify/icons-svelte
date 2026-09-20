<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3qx18b1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3qx18b1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:backward" {...props}></Icon>
