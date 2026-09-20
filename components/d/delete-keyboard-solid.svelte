<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-paljbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r-paljbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:delete-keyboard-solid" {...props}></Icon>
