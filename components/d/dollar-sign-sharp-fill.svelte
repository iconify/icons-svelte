<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm-yfu1dw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-yfu1dw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:dollar-sign-sharp-fill" {...props}></Icon>
