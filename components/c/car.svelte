<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivwl1-arg.css';
import '../../css/z/z7-npobbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivwl1-arg"/><path class="z7-npobbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:car" {...props}></Icon>
