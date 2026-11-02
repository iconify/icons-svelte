<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee0-kbbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee0-kbbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:equal-not-fill" {...props}></Icon>
