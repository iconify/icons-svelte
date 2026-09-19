<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awwatjbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="awwatjbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:delicious" {...props}></Icon>
