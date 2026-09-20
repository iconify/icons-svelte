<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv5a3xb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lv5a3xb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:crown-solid" {...props}></Icon>
