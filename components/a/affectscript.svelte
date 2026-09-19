<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm4n88bcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="lm4n88bcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:affectscript" {...props}></Icon>
