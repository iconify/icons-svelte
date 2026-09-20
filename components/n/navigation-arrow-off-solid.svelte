<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_byzp5sk.css';
import '../../css/g/gj4pehvxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j_byzp5sk"/><path clip-rule="evenodd" class="gj4pehvxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:navigation-arrow-off-solid" {...props}></Icon>
