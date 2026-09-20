<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsmgo6kln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsmgo6kln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:gesture-expansion-filled" {...props}></Icon>
