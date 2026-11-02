<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugnsamf_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugnsamf_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heart-plus-line" {...props}></Icon>
