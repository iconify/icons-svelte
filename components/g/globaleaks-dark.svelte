<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aet668bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aet668bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:globaleaks-dark" {...props}></Icon>
