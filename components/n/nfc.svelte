<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6_co1nfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6_co1nfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:nfc" {...props}></Icon>
