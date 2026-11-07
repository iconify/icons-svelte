<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfa77bcts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pfa77bcts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:garage-bold" {...props}></Icon>
