<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg_sfhb4g.css';
import '../../css/v/vw_qo7apa.css';
import '../../css/b/bsihc0byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fg_sfhb4g"/><path class="vw_qo7apa"/><path class="bsihc0byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:certificate-20" {...props}></Icon>
