<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj5pqqy1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj5pqqy1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lock-open-fill" {...props}></Icon>
