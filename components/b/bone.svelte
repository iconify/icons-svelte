<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl1-zyvbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl1-zyvbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bone" {...props}></Icon>
