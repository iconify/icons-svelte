<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz5rt2evi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iz5rt2evi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:aurelia" {...props}></Icon>
