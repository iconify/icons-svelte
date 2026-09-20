<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iudi4hfwd.css';
import '../../css/l/l8rtx08ws.css';
import '../../css/k/k-4btpb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000.005};
const content = `<path class="iudi4hfwd"/><path class="l8rtx08ws"/><path class="k-4btpb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cnn-international" {...props}></Icon>
