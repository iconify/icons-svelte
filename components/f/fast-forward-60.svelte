<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zugi9wbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zugi9wbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fast-forward-60" {...props}></Icon>
