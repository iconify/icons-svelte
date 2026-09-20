<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2q_edbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2q_edbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:download-stack" {...props}></Icon>
