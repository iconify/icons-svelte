<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a599-h6nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a599-h6nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:open-umbrella-solid" {...props}></Icon>
