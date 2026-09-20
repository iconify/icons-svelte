<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgkokibcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bgkokibcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:change-background-transparent" {...props}></Icon>
