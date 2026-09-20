<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpl-z2bob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="zpl-z2bob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:beat" {...props}></Icon>
