<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcnwy08sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcnwy08sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:religion-judaic" {...props}></Icon>
