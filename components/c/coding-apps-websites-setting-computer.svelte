<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z40llcbyn.css';
import '../../css/g/g2_3tpb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z40llcbyn"/><path class="g2_3tpb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:coding-apps-websites-setting-computer" {...props}></Icon>
