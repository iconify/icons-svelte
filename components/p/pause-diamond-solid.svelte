<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vryi60c7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vryi60c7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:pause-diamond-solid" {...props}></Icon>
