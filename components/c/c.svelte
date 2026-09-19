<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srivz4b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="srivz4b0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:c" {...props}></Icon>
