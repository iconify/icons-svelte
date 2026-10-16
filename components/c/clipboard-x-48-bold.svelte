<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u95e4sw8e.css';
import '../../css/f/f7w-71w7o.css';
import '../../css/v/vix52acse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u95e4sw8e"/><path class="f7w-71w7o"/><path class="vix52acse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clipboard-x-48-bold" {...props}></Icon>
