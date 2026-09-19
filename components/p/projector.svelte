<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gveut4b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":640};
const content = `<path class="gveut4b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:projector" {...props}></Icon>
