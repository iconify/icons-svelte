<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/przcfuwhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="przcfuwhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mp3-outline" {...props}></Icon>
