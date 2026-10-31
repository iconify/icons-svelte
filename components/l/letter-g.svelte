<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwwgftb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwwgftb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:letter-g" {...props}></Icon>
