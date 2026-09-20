<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwj4ck9iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uwj4ck9iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:distribute-objects-vertically" {...props}></Icon>
