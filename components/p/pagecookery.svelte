<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt_enpims.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kt_enpims"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pagecookery" {...props}></Icon>
