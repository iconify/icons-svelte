<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7l3azxnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s7l3azxnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:paper-airplane" {...props}></Icon>
