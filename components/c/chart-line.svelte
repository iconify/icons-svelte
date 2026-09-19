<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r64ajbc7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r64ajbc7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chart-line" {...props}></Icon>
