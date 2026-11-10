<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7yrwubkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g7yrwubkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:calendar-exclamation-16-solid" {...props}></Icon>
