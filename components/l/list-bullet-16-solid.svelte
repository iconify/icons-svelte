<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezto7sb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ezto7sb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:list-bullet-16-solid" {...props}></Icon>
