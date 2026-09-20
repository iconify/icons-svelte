<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjmor_bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjmor_bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:hilton" {...props}></Icon>
