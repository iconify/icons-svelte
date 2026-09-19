<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvxof8u4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvxof8u4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:heading-h3" {...props}></Icon>
