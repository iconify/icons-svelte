<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2cylregb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x2cylregb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bulb-2-fill" {...props}></Icon>
