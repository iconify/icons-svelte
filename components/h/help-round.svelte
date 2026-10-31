<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk-vu9vai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gk-vu9vai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:help-round" {...props}></Icon>
