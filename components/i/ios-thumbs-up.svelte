<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhso_9btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lhso_9btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-thumbs-up" {...props}></Icon>
