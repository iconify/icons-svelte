<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv4wiccsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="mv4wiccsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:parthenon" {...props}></Icon>
