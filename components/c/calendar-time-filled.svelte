<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5c7b29av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g5c7b29av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:calendar-time-filled" {...props}></Icon>
