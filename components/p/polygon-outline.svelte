<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_ks-y9lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b_ks-y9lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:polygon-outline" {...props}></Icon>
