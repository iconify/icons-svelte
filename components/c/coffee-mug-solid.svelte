<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck3c2j_ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ck3c2j_ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:coffee-mug-solid" {...props}></Icon>
