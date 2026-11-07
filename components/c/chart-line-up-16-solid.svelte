<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9qjobbej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k9qjobbej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chart-line-up-16-solid" {...props}></Icon>
