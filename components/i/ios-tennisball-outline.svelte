<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in1283djp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="in1283djp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-tennisball-outline" {...props}></Icon>
