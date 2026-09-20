<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfc0hbabl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="yfc0hbabl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:clipboard" {...props}></Icon>
