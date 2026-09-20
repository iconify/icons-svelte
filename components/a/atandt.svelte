<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4cce8b_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4cce8b_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:atandt" {...props}></Icon>
