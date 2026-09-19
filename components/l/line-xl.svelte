<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akp48p50j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akp48p50j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:line-xl" {...props}></Icon>
