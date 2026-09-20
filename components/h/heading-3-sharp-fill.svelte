<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_lglebah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_lglebah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:heading-3-sharp-fill" {...props}></Icon>
