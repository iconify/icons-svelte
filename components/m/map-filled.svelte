<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb56yvrpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb56yvrpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-filled" {...props}></Icon>
