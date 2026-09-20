<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe6i24l2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe6i24l2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:percent-diamond" {...props}></Icon>
