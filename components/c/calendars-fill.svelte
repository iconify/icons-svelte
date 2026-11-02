<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsuzv0s2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsuzv0s2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendars-fill" {...props}></Icon>
