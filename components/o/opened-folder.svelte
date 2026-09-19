<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7g52cc-s.css';
import '../../css/p/pftszrbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s7g52cc-s"/><path class="pftszrbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:opened-folder" {...props}></Icon>
