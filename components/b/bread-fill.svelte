<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3t__ccaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t3t__ccaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bread-fill" {...props}></Icon>
