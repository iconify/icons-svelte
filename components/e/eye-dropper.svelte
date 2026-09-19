<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqrwk8bxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gqrwk8bxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:eye-dropper" {...props}></Icon>
