<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oguqnobco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oguqnobco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:paper-airplane-20-solid" {...props}></Icon>
