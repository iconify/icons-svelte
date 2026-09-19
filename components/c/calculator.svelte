<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck3ktbcfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck3ktbcfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:calculator" {...props}></Icon>
