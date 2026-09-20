<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl17irjlu.css';
import '../../css/f/fjge1xbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="xl17irjlu"/><path class="fjge1xbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pulsarr" {...props}></Icon>
