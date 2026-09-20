<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vni83uqvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vni83uqvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:flu-mask-remix" {...props}></Icon>
