<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaqd1-b4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1088,"height":1792};
const content = `<path class="oaqd1-b4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:odnoklassniki" {...props}></Icon>
