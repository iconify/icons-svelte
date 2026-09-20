<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbqhcvwag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbqhcvwag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pyramid-plus" {...props}></Icon>
