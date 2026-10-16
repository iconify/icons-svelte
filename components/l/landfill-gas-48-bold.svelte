<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6wqg-hrr.css';
import '../../css/c/ch_p76tdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s6wqg-hrr"/><path class="ch_p76tdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:landfill-gas-48-bold" {...props}></Icon>
