<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gedt4o8uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gedt4o8uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-arrow-left-line" {...props}></Icon>
