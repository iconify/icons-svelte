<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhqm7bb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhqm7bb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrows-to-axis-dashed-vertical" {...props}></Icon>
