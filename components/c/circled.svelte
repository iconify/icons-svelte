<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-u0geb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e-u0geb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circled" {...props}></Icon>
