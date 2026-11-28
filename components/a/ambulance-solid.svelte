<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jobicj7gy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jobicj7gy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ambulance-solid" {...props}></Icon>
