<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnv7htbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnv7htbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-right" {...props}></Icon>
