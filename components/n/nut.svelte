<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c02ksmlsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c02ksmlsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:nut" {...props}></Icon>
