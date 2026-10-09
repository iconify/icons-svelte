<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzn-fsb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vzn-fsb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:caret-right-48" {...props}></Icon>
