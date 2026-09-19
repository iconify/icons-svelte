<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pscki0bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pscki0bkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:laptop-fill" {...props}></Icon>
