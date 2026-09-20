<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6ku1w02h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l6ku1w02h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:phone2" {...props}></Icon>
