<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqi7m4bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqi7m4bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:maximize-one" {...props}></Icon>
