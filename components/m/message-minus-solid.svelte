<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huke5hvmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="huke5hvmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:message-minus-solid" {...props}></Icon>
