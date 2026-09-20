<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbkzf60tt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zbkzf60tt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campsite-with-yen-yuan" {...props}></Icon>
