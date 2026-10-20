<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0s85yyfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i0s85yyfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:option-key-48-bold" {...props}></Icon>
