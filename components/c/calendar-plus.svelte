<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge9gbalhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ge9gbalhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:calendar-plus" {...props}></Icon>
