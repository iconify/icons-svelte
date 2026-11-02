<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2w5iac6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2w5iac6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exposure-fill" {...props}></Icon>
