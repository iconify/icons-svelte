<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iccc16bhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iccc16bhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:font-size-fill" {...props}></Icon>
