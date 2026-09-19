<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t54kcbc4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t54kcbc4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:lock" {...props}></Icon>
