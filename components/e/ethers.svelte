<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g43-tlbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g43-tlbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ethers" {...props}></Icon>
