<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve53p6bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve53p6bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:puzzle-fill-round" {...props}></Icon>
