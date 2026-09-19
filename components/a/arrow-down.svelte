<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqur7u31c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":448};
const content = `<path class="gqur7u31c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:arrow-down" {...props}></Icon>
