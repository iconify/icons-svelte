<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s63b25boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s63b25boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:qase" {...props}></Icon>
