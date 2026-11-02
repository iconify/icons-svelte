<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cacy0409r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cacy0409r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:document-3-fill" {...props}></Icon>
