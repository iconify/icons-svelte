<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh-smq3-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zh-smq3-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:musicbrainz-light" {...props}></Icon>
