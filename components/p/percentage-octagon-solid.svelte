<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4hjl6bad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4hjl6bad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:percentage-octagon-solid" {...props}></Icon>
