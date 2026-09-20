<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3-r53wrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="e3-r53wrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pet-paw-remix" {...props}></Icon>
