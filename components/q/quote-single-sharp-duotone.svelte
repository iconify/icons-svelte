<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y84nn4bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y84nn4bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:quote-single-sharp-duotone" {...props}></Icon>
