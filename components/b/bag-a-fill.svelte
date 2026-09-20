<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzl4ict-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzl4ict-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:bag-a-fill" {...props}></Icon>
