<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7mb3_b4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v7mb3_b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:heartbeat2x-outline" {...props}></Icon>
