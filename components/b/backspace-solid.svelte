<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdlmu3blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="sdlmu3blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:backspace-solid" {...props}></Icon>
