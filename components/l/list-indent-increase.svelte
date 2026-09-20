<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n__gb0bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n__gb0bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:list-indent-increase" {...props}></Icon>
