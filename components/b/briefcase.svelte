<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0djt_8ng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h0djt_8ng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:briefcase" {...props}></Icon>
