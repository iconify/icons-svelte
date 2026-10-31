<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug46cjb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug46cjb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-turn-up-left-bulk-round" {...props}></Icon>
