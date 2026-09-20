<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr61sd6wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mr61sd6wt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:intel" {...props}></Icon>
