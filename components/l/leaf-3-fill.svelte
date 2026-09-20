<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsnqcpl0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gsnqcpl0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:leaf-3-fill" {...props}></Icon>
