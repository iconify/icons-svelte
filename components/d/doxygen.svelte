<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dztqf8b0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dztqf8b0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:doxygen" {...props}></Icon>
