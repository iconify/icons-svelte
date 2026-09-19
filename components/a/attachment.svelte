<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spvce6bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spvce6bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:attachment" {...props}></Icon>
