<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgh8ogqyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kgh8ogqyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:add-circle-remix" {...props}></Icon>
