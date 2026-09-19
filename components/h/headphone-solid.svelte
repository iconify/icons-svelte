<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uznf0tbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uznf0tbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:headphone-solid" {...props}></Icon>
