<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i12ljv2bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i12ljv2bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:female-sign" {...props}></Icon>
