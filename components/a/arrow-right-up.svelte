<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boz_pggbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="boz_pggbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:arrow-right-up" {...props}></Icon>
