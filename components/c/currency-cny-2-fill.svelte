<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy4sw6zrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sy4sw6zrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-cny-2-fill" {...props}></Icon>
