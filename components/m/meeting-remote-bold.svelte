<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax4al5w4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax4al5w4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:meeting-remote-bold" {...props}></Icon>
