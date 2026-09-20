<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr0wuj7lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pr0wuj7lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:loading-circle-flat" {...props}></Icon>
