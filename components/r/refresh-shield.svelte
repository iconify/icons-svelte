<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axsftvk0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="axsftvk0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:refresh-shield" {...props}></Icon>
