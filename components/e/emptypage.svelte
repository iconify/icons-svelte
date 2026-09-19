<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw-pbdcck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pw-pbdcck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:emptypage" {...props}></Icon>
