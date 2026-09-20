<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1-yl58zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1-yl58zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:alchemy" {...props}></Icon>
