<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj-p7ldds.css';
import '../../css/o/o67rmiljq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sj-p7ldds"/><path class="o67rmiljq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:rightspeaker" {...props}></Icon>
