<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3bo38t3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b3bo38t3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:airplane-disabled-remix" {...props}></Icon>
