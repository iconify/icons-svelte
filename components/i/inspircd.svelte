<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5x_o2bjy.css';
import '../../css/z/zo1w86b7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a5x_o2bjy"/><path class="zo1w86b7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:inspircd" {...props}></Icon>
