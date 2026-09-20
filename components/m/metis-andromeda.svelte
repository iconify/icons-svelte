<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr1jnvb_y.css';
import '../../css/u/umd4-qbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr1jnvb_y"/><path class="umd4-qbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:metis-andromeda" {...props}></Icon>
