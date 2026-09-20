<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijgpwoblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijgpwoblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:brain-2-line" {...props}></Icon>
