<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpqr5jbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kpqr5jbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:peg" {...props}></Icon>
