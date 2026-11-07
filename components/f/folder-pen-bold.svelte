<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jppf41bdk.css';
import '../../css/j/j-xg48kfo.css';
import '../../css/t/tnn4k8b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jppf41bdk"/><path class="j-xg48kfo"/><path clip-rule="evenodd" class="tnn4k8b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-pen-bold" {...props}></Icon>
