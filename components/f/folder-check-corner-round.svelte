<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6ni-ab2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6ni-ab2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-check-corner-round" {...props}></Icon>
