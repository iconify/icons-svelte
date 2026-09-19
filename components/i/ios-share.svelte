<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0fq7z9-w.css';
import '../../css/h/hzfhhfw2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d0fq7z9-w"/><path class="hzfhhfw2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-share" {...props}></Icon>
