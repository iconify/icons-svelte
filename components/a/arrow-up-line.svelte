<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gapgg0w6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gapgg0w6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-up-line" {...props}></Icon>
