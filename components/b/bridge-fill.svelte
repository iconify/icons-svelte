<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6xl8rbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k6xl8rbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bridge-fill" {...props}></Icon>
