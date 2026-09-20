<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knt06ccrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="knt06ccrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:dashboard-3-solid" {...props}></Icon>
