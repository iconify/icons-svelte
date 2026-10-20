<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc2oi_bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc2oi_bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cable" {...props}></Icon>
