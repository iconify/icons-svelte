<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1tym-4tt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1tym-4tt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:japanese-yen-sharp-two-tone" {...props}></Icon>
