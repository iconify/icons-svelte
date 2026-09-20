<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzx2ml0ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzx2ml0ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-down" {...props}></Icon>
