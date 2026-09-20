<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oomu49twr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oomu49twr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:browser-minus" {...props}></Icon>
