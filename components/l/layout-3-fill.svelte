<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3k_ccbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3k_ccbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-3-fill" {...props}></Icon>
