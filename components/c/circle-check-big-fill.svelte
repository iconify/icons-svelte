<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg5ua8opk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tg5ua8opk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-check-big-fill" {...props}></Icon>
