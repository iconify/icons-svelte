<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw0an_lir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dw0an_lir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:package-up" {...props}></Icon>
