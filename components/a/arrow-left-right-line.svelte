<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytj3n3bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytj3n3bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-left-right-line" {...props}></Icon>
