<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6odmw4gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="y6odmw4gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:agenda" {...props}></Icon>
