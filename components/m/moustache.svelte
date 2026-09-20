<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b20da4xzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b20da4xzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:moustache" {...props}></Icon>
