<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gonmgov-i.css';
import '../../css/s/s1ew34b9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<circle class="gonmgov-i"/><path class="s1ew34b9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:camera" {...props}></Icon>
