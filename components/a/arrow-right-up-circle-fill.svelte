<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sczek63md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sczek63md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-right-up-circle-fill" {...props}></Icon>
