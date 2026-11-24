<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4ea79bqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k4ea79bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:rabbit-filled" {...props}></Icon>
