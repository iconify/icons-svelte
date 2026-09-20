<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo6c03b0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yo6c03b0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-waterfall-sharp-fill" {...props}></Icon>
