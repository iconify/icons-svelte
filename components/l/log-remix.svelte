<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us5-5pbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="us5-5pbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:log-remix" {...props}></Icon>
