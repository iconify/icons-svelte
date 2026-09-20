<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veyfuxbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="veyfuxbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chevron-up-fill" {...props}></Icon>
