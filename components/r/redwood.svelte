<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfo87_b9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cfo87_b9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:redwood" {...props}></Icon>
