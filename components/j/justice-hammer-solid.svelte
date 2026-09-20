<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9di_yx8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k9di_yx8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:justice-hammer-solid" {...props}></Icon>
