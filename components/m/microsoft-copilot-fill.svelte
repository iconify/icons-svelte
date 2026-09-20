<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxj-dx65r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxj-dx65r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:microsoft-copilot-fill" {...props}></Icon>
