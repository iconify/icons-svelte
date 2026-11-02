<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpa6sprsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpa6sprsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-minus-fill" {...props}></Icon>
