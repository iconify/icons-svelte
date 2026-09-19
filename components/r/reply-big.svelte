<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foztiubet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="foztiubet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:reply-big" {...props}></Icon>
