<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svh25cwvl.css';
import '../../css/m/m4c7wqb2i.css';
import '../../css/m/mqymo7s1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="svh25cwvl"/><path class="m4c7wqb2i"/><path class="mqymo7s1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:radicle-light" {...props}></Icon>
