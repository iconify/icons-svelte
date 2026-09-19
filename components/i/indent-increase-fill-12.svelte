<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xadmxrn2z.css';
import '../../css/t/to17vzthq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xadmxrn2z"/><path class="to17vzthq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:indent-increase-fill-12" {...props}></Icon>
