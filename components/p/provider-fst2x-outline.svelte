<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6ppj1_bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="w6ppj1_bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:provider-fst2x-outline" {...props}></Icon>
