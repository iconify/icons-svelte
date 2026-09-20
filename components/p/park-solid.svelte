<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6y15mb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j6y15mb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:park-solid" {...props}></Icon>
