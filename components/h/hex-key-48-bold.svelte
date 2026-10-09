<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg8ope4jq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dg8ope4jq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hex-key-48-bold" {...props}></Icon>
