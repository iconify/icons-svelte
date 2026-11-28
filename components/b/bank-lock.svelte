<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et3hl_bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="et3hl_bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bank-lock" {...props}></Icon>
