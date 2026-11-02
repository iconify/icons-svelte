<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4vyjv2jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4vyjv2jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:na-fill" {...props}></Icon>
