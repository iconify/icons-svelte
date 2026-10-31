<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz98x5bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz98x5bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-plus-fill-round" {...props}></Icon>
