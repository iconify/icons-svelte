<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei_iqhb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ei_iqhb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:dropbox-logo-remix" {...props}></Icon>
