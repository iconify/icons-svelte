<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3z00db-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t3z00db-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-paper-plane" {...props}></Icon>
