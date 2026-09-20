<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bufq13isk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bufq13isk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-activity-sharp-fill" {...props}></Icon>
