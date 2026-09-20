<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om1bhbc1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="om1bhbc1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:location-pin-store-solid" {...props}></Icon>
