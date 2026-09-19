<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b783a2h0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b783a2h0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:guide-dog2x-outline" {...props}></Icon>
