<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvbo4tboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xvbo4tboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:battery-horizontal-charging" {...props}></Icon>
