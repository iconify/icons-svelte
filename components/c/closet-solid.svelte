<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guro_cc7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="guro_cc7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:closet-solid" {...props}></Icon>
