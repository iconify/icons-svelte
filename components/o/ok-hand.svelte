<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt9b6kjbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kt9b6kjbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ok-hand" {...props}></Icon>
