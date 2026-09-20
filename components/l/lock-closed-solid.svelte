<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwo3tnbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zwo3tnbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:lock-closed-solid" {...props}></Icon>
