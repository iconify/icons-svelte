<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq7zz_bpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nq7zz_bpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:nano-stores" {...props}></Icon>
