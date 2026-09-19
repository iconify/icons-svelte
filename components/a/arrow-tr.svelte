<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2r8b5pqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2r8b5pqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrow-tr" {...props}></Icon>
