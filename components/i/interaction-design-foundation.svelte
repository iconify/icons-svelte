<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mii9zibzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mii9zibzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:interaction-design-foundation" {...props}></Icon>
