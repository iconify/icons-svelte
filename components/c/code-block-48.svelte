<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsmhpgwcs.css';
import '../../css/f/fh8g7ab6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tsmhpgwcs"/><path class="fh8g7ab6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:code-block-48" {...props}></Icon>
