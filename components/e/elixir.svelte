<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk6mzs3do.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qk6mzs3do"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:elixir" {...props}></Icon>
