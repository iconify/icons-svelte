<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibdu4nf8k.css';
import '../../css/s/s_4tnnghm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ibdu4nf8k"/><path class="s_4tnnghm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dog-48-bold" {...props}></Icon>
