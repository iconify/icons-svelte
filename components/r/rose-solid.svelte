<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwuz2acbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jwuz2acbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:rose-solid" {...props}></Icon>
