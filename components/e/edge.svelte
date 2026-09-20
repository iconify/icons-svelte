<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bngtq2bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bngtq2bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:edge" {...props}></Icon>
