<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmb49sbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hmb49sbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:marker-tip" {...props}></Icon>
