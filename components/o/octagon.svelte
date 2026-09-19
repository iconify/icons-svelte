<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbl9e-bnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbl9e-bnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:octagon" {...props}></Icon>
