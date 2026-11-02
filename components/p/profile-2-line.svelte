<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc24c_b4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qc24c_b4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:profile-2-line" {...props}></Icon>
