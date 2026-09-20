<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueuomgrie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ueuomgrie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:play" {...props}></Icon>
