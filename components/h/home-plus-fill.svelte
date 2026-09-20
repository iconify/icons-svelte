<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixr32ep7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixr32ep7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:home-plus-fill" {...props}></Icon>
