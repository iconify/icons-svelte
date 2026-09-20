<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2crgeb7t.css';
import '../../css/q/qwqwk1bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="w2crgeb7t"/><path clip-rule="evenodd" class="qwqwk1bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloudpi-dark" {...props}></Icon>
