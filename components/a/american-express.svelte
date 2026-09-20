<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_dm_hbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_dm_hbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:american-express" {...props}></Icon>
