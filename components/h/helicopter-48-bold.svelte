<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tomb__uya.css';
import '../../css/v/vd19ejbdy.css';
import '../../css/f/fs7__xl7e.css';
import '../../css/x/xw6ho4bxz.css';
import '../../css/v/vq3mlfbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tomb__uya"/><path class="vd19ejbdy"/><path class="fs7__xl7e"/><path class="xw6ho4bxz"/><path class="vq3mlfbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:helicopter-48-bold" {...props}></Icon>
