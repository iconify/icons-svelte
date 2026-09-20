<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tltgrpfit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tltgrpfit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panels-right-bottom-sharp-fill" {...props}></Icon>
