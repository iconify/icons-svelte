<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3q788btk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3q788btk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:indent-decrease" {...props}></Icon>
