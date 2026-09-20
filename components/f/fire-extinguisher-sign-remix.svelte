<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hym1jybwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hym1jybwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:fire-extinguisher-sign-remix" {...props}></Icon>
