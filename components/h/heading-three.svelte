<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig7lx8b2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ig7lx8b2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heading-three" {...props}></Icon>
