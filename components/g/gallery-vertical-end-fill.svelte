<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2bv0_bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2bv0_bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gallery-vertical-end-fill" {...props}></Icon>
