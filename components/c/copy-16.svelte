<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs5cgacrv.css';
import '../../css/o/o28durbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fs5cgacrv"/><path class="o28durbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:copy-16" {...props}></Icon>
