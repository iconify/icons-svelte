<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qan8l4b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qan8l4b2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:cloud-filled" {...props}></Icon>
