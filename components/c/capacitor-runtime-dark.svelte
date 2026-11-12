<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbhczis_n.css';
import '../../css/g/g6y54xlpm.css';
import '../../css/u/up9gopgdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hbhczis_n"/><path class="g6y54xlpm"/><path class="up9gopgdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:capacitor-runtime-dark" {...props}></Icon>
