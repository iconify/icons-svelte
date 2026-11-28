<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo37sdstw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo37sdstw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-manual-operation-solid" {...props}></Icon>
