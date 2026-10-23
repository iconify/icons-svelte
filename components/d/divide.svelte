<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3saow1yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3saow1yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:divide" {...props}></Icon>
