<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsa2r967w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsa2r967w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:amazonlumberyard" {...props}></Icon>
