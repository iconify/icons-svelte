<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezsh2vbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ezsh2vbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:calendar-heart-solid" {...props}></Icon>
