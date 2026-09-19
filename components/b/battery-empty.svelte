<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iic6q4bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iic6q4bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:battery-empty" {...props}></Icon>
