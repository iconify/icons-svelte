<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lafxaf8vs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lafxaf8vs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:octagon-round" {...props}></Icon>
