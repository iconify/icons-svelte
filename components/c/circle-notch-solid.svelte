<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn4keacsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn4keacsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:circle-notch-solid" {...props}></Icon>
