<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-lf7acey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="o-lf7acey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:flask" {...props}></Icon>
