<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox_5e8bhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox_5e8bhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:calendar-plus-2" {...props}></Icon>
