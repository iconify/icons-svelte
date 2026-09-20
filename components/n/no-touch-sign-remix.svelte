<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysaxjs38j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ysaxjs38j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:no-touch-sign-remix" {...props}></Icon>
