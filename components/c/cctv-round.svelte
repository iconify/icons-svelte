<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds3n3dbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds3n3dbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cctv-round" {...props}></Icon>
