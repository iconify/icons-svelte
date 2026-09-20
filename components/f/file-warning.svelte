<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-z4ovd-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-z4ovd-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:file-warning" {...props}></Icon>
