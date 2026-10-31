<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb1_zvdgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lb1_zvdgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:home-gloss" {...props}></Icon>
