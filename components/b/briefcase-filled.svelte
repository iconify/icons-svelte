<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hklz-72lg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hklz-72lg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:briefcase-filled" {...props}></Icon>
