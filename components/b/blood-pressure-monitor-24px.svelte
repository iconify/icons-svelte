<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrbjelblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nrbjelblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-pressure-monitor-24px" {...props}></Icon>
