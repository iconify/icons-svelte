<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwy-gkbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vwy-gkbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:calculator-filled" {...props}></Icon>
