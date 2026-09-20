<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn5db_b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="kn5db_b0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:brush-alt" {...props}></Icon>
