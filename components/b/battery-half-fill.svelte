<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm-cbjo0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bm-cbjo0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:battery-half-fill" {...props}></Icon>
