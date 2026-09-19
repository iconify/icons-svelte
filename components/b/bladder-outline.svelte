<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6uue9b2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="h6uue9b2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:bladder-outline" {...props}></Icon>
