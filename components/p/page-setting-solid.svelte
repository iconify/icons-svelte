<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgs7_jqez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lgs7_jqez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:page-setting-solid" {...props}></Icon>
