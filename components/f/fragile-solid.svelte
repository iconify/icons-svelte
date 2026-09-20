<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6gk6tkiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e6gk6tkiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:fragile-solid" {...props}></Icon>
