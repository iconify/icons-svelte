<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpbek_6vs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpbek_6vs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:lungs" {...props}></Icon>
