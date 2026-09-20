<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uao0u1bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uao0u1bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:braille-blind" {...props}></Icon>
