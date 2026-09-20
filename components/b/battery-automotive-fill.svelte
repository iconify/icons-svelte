<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt2ubuxgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tt2ubuxgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:battery-automotive-fill" {...props}></Icon>
