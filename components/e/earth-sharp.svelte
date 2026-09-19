<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4csvlige.css';
import '../../css/y/y--a8-brh.css';
import '../../css/j/jap_-fj2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p4csvlige"/><path class="y--a8-brh"/><path class="jap_-fj2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:earth-sharp" {...props}></Icon>
