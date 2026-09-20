<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghz--5eim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghz--5eim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-multiselect" {...props}></Icon>
