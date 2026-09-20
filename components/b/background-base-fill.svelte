<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhk-zwbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhk-zwbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:background-base-fill" {...props}></Icon>
