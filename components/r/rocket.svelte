<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6jww25rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6jww25rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:rocket" {...props}></Icon>
