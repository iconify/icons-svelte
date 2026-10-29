<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6avd7p5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6avd7p5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:microwave-solid" {...props}></Icon>
