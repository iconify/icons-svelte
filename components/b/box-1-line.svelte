<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x505yqb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x505yqb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:box-1-line" {...props}></Icon>
