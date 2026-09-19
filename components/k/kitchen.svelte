<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr2_dksop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pr2_dksop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:kitchen" {...props}></Icon>
