<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcadaubyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcadaubyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:format-italic" {...props}></Icon>
