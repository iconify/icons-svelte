<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2be4_ncf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j2be4_ncf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gitlab-fill-16" {...props}></Icon>
