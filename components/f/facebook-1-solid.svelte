<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khmmrdbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="khmmrdbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:facebook-1-solid" {...props}></Icon>
