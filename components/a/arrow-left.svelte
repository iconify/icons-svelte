<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av-0zqb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av-0zqb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:arrow-left" {...props}></Icon>
