<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrhq1cc2r.css';
import '../../css/i/ivt8o-bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrhq1cc2r"/><path class="ivt8o-bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bible" {...props}></Icon>
