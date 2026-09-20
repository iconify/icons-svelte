<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w739r15xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w739r15xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:close-circle-dash-fill" {...props}></Icon>
