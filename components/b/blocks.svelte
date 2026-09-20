<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av-ms0saj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av-ms0saj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:blocks" {...props}></Icon>
