<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v24sd8uqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v24sd8uqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:elm" {...props}></Icon>
