<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix1bs9bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ix1bs9bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bolt-off-48-bold" {...props}></Icon>
