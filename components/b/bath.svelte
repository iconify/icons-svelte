<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am1phpbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am1phpbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bath" {...props}></Icon>
