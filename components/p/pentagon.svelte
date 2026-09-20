<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azi51ub6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azi51ub6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:pentagon" {...props}></Icon>
