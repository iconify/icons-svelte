<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f99k2xbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f99k2xbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-sitting-on-lifeguard-stand" {...props}></Icon>
