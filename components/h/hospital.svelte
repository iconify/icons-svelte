<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tss4qzbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tss4qzbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:hospital" {...props}></Icon>
