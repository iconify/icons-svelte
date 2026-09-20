<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpbmm38ti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpbmm38ti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:flask-round" {...props}></Icon>
