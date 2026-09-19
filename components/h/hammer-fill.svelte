<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isoz64bhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="isoz64bhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:hammer-fill" {...props}></Icon>
