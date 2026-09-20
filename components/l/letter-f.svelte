<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aumvg2bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aumvg2bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-f" {...props}></Icon>
