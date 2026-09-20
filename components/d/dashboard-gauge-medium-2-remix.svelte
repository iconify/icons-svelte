<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs9y-_bxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fs9y-_bxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:dashboard-gauge-medium-2-remix" {...props}></Icon>
