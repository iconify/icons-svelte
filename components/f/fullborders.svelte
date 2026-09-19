<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_igwibwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":960};
const content = `<path class="i_igwibwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fullborders" {...props}></Icon>
