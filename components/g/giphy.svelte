<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz4mkebaq.css';
import '../../css/y/ylzf4_8rg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lz4mkebaq"/><path class="ylzf4_8rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:giphy" {...props}></Icon>
