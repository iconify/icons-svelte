<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv0fefbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sv0fefbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:hard-drive-2-solid" {...props}></Icon>
