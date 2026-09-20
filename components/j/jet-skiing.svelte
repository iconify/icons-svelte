<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkz36vbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="dkz36vbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:jet-skiing" {...props}></Icon>
