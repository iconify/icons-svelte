<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psvv09pyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psvv09pyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:pin-outline" {...props}></Icon>
