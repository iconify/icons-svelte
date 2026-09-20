<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nueifsb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nueifsb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:compass-navigator-solid" {...props}></Icon>
