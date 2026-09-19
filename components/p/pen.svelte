<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd064tiam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":472};
const content = `<path class="kd064tiam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:pen" {...props}></Icon>
