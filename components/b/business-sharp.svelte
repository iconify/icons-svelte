<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4zsyabzx.css';
import '../../css/a/alear2y7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b4zsyabzx"/><path class="alear2y7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:business-sharp" {...props}></Icon>
