<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imsy5jbgi.css';
import '../../css/h/hgn2g5biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imsy5jbgi"/><path class="hgn2g5biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:location-alt" {...props}></Icon>
