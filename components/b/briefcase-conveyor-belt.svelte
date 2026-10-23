<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g615euncf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g615euncf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:briefcase-conveyor-belt" {...props}></Icon>
