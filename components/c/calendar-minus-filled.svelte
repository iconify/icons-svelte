<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd7jidc8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xd7jidc8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:calendar-minus-filled" {...props}></Icon>
