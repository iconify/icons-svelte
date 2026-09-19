<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njkt2bj_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="njkt2bj_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:edit-large" {...props}></Icon>
