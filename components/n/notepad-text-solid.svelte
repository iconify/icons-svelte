<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ois0iqb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ois0iqb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:notepad-text-solid" {...props}></Icon>
