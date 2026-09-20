<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl70dwxfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nl70dwxfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:controller-1-solid" {...props}></Icon>
