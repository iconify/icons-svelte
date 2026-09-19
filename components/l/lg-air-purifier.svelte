<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eft6sfbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eft6sfbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lg-air-purifier" {...props}></Icon>
