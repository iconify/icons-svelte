<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6-ai6bkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t6-ai6bkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:information-circle-solid" {...props}></Icon>
