<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pehby3vco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pehby3vco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:globe-europe-africa" {...props}></Icon>
