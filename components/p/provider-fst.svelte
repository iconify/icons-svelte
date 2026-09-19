<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmsw3db2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nmsw3db2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:provider-fst" {...props}></Icon>
