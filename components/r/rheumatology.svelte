<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-zu11bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t-zu11bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:rheumatology" {...props}></Icon>
