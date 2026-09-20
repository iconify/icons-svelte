<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da1i54d5m.css';
import '../../css/o/oensybc-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="da1i54d5m"/><path class="oensybc-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-salt-open" {...props}></Icon>
