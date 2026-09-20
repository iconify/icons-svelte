<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm69jwb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fm69jwb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:mute" {...props}></Icon>
