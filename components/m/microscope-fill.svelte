<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgtba__ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hgtba__ty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:microscope-fill" {...props}></Icon>
