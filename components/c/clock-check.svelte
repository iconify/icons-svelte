<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5heg0yot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5heg0yot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clock-check" {...props}></Icon>
