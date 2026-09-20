<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoaml5x3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eoaml5x3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:accessible-icon-alt" {...props}></Icon>
