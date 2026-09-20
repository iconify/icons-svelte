<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0w9sbztq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0w9sbztq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:book-open" {...props}></Icon>
