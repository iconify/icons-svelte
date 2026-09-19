<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp147-bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mp147-bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:cash-solid" {...props}></Icon>
