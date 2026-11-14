<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv_4w2mzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bv_4w2mzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ban" {...props}></Icon>
