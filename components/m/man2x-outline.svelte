<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybjb7-_9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ybjb7-_9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:man2x-outline" {...props}></Icon>
