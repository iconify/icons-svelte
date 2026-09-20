<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr7sn_xxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kr7sn_xxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:navigation-fill" {...props}></Icon>
