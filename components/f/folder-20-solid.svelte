<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et4u17bqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="et4u17bqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:folder-20-solid" {...props}></Icon>
