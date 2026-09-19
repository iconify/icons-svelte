<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldqp1sbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ldqp1sbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-drowning" {...props}></Icon>
