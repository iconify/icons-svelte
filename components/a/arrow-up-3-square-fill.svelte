<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke91w5bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ke91w5bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-up-3-square-fill" {...props}></Icon>
