<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep01_69oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="ep01_69oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:diningroom" {...props}></Icon>
