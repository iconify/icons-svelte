<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bigtc4wcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bigtc4wcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:calendar-exclamation" {...props}></Icon>
