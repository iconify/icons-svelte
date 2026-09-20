<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixrr6gp5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ixrr6gp5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:business-progress-bar-2-solid" {...props}></Icon>
