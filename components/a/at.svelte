<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5z7xj-nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s5z7xj-nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:at" {...props}></Icon>
