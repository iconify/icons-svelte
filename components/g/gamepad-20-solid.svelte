<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f33c-52ev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="f33c-52ev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gamepad-20-solid" {...props}></Icon>
