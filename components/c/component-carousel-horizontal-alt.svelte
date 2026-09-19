<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfop2ebsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nfop2ebsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:component-carousel-horizontal-alt" {...props}></Icon>
