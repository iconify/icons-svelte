<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y83n522hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y83n522hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:printer-sharp" {...props}></Icon>
