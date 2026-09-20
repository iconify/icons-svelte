<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g99h9zyby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g99h9zyby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-rubel-2-fill" {...props}></Icon>
