<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o54f7nakg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="o54f7nakg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pointer-top" {...props}></Icon>
