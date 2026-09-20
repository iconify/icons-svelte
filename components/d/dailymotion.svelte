<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i23ml48ll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i23ml48ll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dailymotion" {...props}></Icon>
