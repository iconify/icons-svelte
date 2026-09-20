<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t76ezw5zz.css';
import '../../css/v/vah_3dbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t76ezw5zz"/><path class="vah_3dbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pixelfin" {...props}></Icon>
