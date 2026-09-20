<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg2sg0nmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wg2sg0nmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:laptop-smartphone-sharp" {...props}></Icon>
