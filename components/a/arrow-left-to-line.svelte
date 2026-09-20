<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w54u5nbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w54u5nbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-left-to-line" {...props}></Icon>
