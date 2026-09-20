<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k81cs34vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k81cs34vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:clock-seven" {...props}></Icon>
