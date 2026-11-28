<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo7og7_1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lo7og7_1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bed-clock" {...props}></Icon>
