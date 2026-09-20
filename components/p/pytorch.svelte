<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcso7vx-z.css';
import '../../css/f/f6wni1b_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="gcso7vx-z"/><path class="f6wni1b_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:pytorch" {...props}></Icon>
