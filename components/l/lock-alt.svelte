<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmi9rovle.css';
import '../../css/f/fttkq3t5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="pmi9rovle"/><path class="fttkq3t5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:lock-alt" {...props}></Icon>
