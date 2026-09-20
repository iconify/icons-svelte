<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx9azprws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx9azprws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:calendar-arrow-up-solid" {...props}></Icon>
