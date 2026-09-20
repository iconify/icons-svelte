<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x140d_bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x140d_bvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:clipboard-minus-outline" {...props}></Icon>
