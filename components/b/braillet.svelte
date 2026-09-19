<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jye27acpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="jye27acpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:braillet" {...props}></Icon>
