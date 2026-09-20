<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egngdtb-a.css';
import '../../css/k/kmix8d4jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egngdtb-a"/><path class="kmix8d4jl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:attic-filled" {...props}></Icon>
