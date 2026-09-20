<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2ts7v77x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b2ts7v77x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-sitting-on-lifeguard-stand-above-water" {...props}></Icon>
