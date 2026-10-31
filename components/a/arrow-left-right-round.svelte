<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mumyvlh7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mumyvlh7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-left-right-round" {...props}></Icon>
