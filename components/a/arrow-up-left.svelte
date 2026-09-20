<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd7j5cbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rd7j5cbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:arrow-up-left" {...props}></Icon>
