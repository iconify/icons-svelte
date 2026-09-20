<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m21fiubni.css';
import '../../css/j/j3h0ykbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m21fiubni"/><path class="j3h0ykbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pufferpanel" {...props}></Icon>
