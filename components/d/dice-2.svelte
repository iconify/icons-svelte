<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-1-n-cnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-1-n-cnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:dice-2" {...props}></Icon>
