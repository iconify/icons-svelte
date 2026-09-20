<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oapubcban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oapubcban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:align-top-2-16" {...props}></Icon>
