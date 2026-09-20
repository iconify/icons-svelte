<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx2p0jj_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx2p0jj_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:i3" {...props}></Icon>
