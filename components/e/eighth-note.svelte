<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a44g3_ugi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a44g3_ugi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:eighth-note" {...props}></Icon>
