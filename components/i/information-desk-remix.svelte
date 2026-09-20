<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe5lb9btn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fe5lb9btn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:information-desk-remix" {...props}></Icon>
