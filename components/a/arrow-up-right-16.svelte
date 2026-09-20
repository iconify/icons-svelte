<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adudr_bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="adudr_bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:arrow-up-right-16" {...props}></Icon>
