<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss9oz9b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ss9oz9b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:recycle-bin-3-solid" {...props}></Icon>
