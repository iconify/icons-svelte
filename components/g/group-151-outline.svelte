<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfdi3-zsx.css';
import '../../css/l/lvrxp9btv.css';
import '../../css/j/jkhrtccjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfdi3-zsx"/><path class="lvrxp9btv"/><path clip-rule="evenodd" class="jkhrtccjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:group-151-outline" {...props}></Icon>
