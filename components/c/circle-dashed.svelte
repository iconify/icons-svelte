<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg8dgjblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg8dgjblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:circle-dashed" {...props}></Icon>
