<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dun9wskug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dun9wskug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:divide" {...props}></Icon>
