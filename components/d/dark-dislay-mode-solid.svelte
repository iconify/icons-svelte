<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf2tp0b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rf2tp0b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:dark-dislay-mode-solid" {...props}></Icon>
