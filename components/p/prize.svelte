<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5a5g2oyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5a5g2oyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:prize" {...props}></Icon>
