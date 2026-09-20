<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7erv32_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7erv32_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:lungs-sharp" {...props}></Icon>
