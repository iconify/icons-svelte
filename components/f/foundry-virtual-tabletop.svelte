<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lohj11b2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lohj11b2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:foundry-virtual-tabletop" {...props}></Icon>
