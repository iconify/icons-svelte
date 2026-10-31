<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etel5odht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etel5odht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:battery-low-round" {...props}></Icon>
