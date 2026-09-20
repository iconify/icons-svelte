<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4wwyn06m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4wwyn06m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bahamut" {...props}></Icon>
