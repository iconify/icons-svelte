<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo9vs-bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qo9vs-bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:paper-airplane-16-solid" {...props}></Icon>
