<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qem3v3brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qem3v3brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-wide-narrow-sharp-fill" {...props}></Icon>
