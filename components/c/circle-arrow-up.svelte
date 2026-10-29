<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrsim2bww.css';
import '../../css/h/h7jt2xa4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k yrsim2bww"/><path class="h7jt2xa4c wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:circle-arrow-up" {...props}></Icon>
