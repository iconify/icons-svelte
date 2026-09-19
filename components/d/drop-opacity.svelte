<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csjj4tjvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="csjj4tjvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:drop-opacity" {...props}></Icon>
