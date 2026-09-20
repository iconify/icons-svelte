<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7rr8ab4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x7rr8ab4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:gallery-2-solid" {...props}></Icon>
