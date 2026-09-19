<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3pk7wb9n.css';
import '../../css/d/d325_0h8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3pk7wb9n"/><path class="d325_0h8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-up-wide-narrow" {...props}></Icon>
