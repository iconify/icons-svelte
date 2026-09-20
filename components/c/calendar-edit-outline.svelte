<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/argc_ccvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="argc_ccvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-edit-outline" {...props}></Icon>
