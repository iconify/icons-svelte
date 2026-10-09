<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x21ra5bou.css';
import '../../css/c/cdhxuqb1b.css';
import '../../css/r/r94vwub7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x21ra5bou"/><path class="cdhxuqb1b"/><path class="r94vwub7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-slow-48" {...props}></Icon>
