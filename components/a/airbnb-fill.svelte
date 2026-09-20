<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukq-8fbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukq-8fbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:airbnb-fill" {...props}></Icon>
