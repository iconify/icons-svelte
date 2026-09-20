<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxwi8fcof.css';
import '../../css/x/xy9vhf6wf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="bxwi8fcof"/><path class="xy9vhf6wf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:gift-solid" {...props}></Icon>
