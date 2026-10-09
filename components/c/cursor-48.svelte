<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvzzzkbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nvzzzkbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cursor-48" {...props}></Icon>
