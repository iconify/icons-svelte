<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utdc-ibes.css';
import '../../css/e/ebr8uinkx.css';
import '../../css/i/ibwikzbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<circle class="utdc-ibes"/><circle class="ebr8uinkx"/><circle class="ibwikzbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:just" {...props}></Icon>
