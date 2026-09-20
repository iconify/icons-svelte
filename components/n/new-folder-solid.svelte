<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb2cbhbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bb2cbhbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:new-folder-solid" {...props}></Icon>
