<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxz9m7bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxz9m7bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:battery-2-fill" {...props}></Icon>
