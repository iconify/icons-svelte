<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwz76--ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gwz76--ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:location2" {...props}></Icon>
