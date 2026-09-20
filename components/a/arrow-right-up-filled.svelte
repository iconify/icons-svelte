<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s99a_kb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s99a_kb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-right-up-filled" {...props}></Icon>
