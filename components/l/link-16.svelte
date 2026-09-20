<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6ktrib3l.css';
import '../../css/f/fxsetnwht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k6ktrib3l"/><path class="fxsetnwht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:link-16" {...props}></Icon>
