<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqscdf3io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqscdf3io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chevrons-down" {...props}></Icon>
