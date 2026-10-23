<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tui3b-bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tui3b-bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:minimize" {...props}></Icon>
