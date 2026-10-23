<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wowm9d2iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wowm9d2iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:biohazard" {...props}></Icon>
