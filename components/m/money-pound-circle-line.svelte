<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8csnibnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8csnibnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:money-pound-circle-line" {...props}></Icon>
