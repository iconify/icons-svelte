<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xou0auhqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xou0auhqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:phone-forward" {...props}></Icon>
