<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9v1q2zst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="m9v1q2zst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:mall-remix" {...props}></Icon>
