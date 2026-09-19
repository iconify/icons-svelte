<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szb_fgbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szb_fgbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-right-02" {...props}></Icon>
