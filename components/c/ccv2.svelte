<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke5xj4b2r.css';
import '../../css/u/u4w6z7bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke5xj4b2r"/><path class="u4w6z7bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ccv2" {...props}></Icon>
