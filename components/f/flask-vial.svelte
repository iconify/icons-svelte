<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3yr3sb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="c3yr3sb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:flask-vial" {...props}></Icon>
