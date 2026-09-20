<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vomp9sbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vomp9sbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:connector" {...props}></Icon>
