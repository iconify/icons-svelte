<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw_k-4pjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hw_k-4pjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:delta-filled" {...props}></Icon>
