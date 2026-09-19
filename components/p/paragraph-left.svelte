<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpht70wqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kpht70wqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:paragraph-left" {...props}></Icon>
