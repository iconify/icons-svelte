<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo8fb39gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oo8fb39gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-chevron-down-fill-round" {...props}></Icon>
