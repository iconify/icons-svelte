<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2e390d8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2e390d8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:chart-trend-down-duotone" {...props}></Icon>
