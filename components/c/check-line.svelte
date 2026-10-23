<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd095q2-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd095q2-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:check-line" {...props}></Icon>
