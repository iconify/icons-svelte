<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qymgqsb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qymgqsb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:nest-middleware" {...props}></Icon>
