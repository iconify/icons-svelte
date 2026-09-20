<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byrp3ybsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="byrp3ybsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-8" {...props}></Icon>
