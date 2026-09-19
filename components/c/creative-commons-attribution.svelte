<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc5y2oeui.css';
import '../../css/g/g3xid1tzo.css';
import '../../css/i/i_60hekpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cc5y2oeui"/><circle class="g3xid1tzo"/><path clip-rule="evenodd" class="i_60hekpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:creative-commons-attribution" {...props}></Icon>
