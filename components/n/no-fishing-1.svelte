<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrkdgzw8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrkdgzw8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:no-fishing-1" {...props}></Icon>
