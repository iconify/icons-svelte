<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tckw8clyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tckw8clyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:dashboard-1-filled" {...props}></Icon>
