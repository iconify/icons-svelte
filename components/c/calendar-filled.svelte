<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_s3f5bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_s3f5bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:calendar-filled" {...props}></Icon>
