<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_fu2bbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="d_fu2bbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:deleteshield" {...props}></Icon>
