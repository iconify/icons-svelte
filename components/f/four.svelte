<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps4efgzki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps4efgzki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:four" {...props}></Icon>
