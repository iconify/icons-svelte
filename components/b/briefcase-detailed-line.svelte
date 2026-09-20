<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcqo08b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcqo08b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:briefcase-detailed-line" {...props}></Icon>
