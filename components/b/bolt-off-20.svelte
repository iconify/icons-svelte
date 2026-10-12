<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyv1r9bwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oyv1r9bwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bolt-off-20" {...props}></Icon>
