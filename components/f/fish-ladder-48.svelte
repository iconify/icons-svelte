<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clpb2bbyt.css';
import '../../css/t/t5bungbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="clpb2bbyt"/><path class="t5bungbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fish-ladder-48" {...props}></Icon>
