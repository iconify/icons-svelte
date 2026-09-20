<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyyvso_mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eyyvso_mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:mail-incoming-solid" {...props}></Icon>
